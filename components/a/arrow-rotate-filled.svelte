<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kef6-gokw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kef6-gokw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-rotate-filled" {...props}></Icon>
