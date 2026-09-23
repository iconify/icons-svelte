<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krnq7hbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krnq7hbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:fish" {...props}></Icon>
