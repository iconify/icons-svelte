<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spc03-04k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spc03-04k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:photocopy-machine" {...props}></Icon>
