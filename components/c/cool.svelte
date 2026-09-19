<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjb5d5f1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjb5d5f1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cool" {...props}></Icon>
