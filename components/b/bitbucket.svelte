<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io988ibmp.css';
import '../../css/r/r02pwbbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io988ibmp"/><path class="r02pwbbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bitbucket" {...props}></Icon>
