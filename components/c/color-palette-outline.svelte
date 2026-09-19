<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6j0c_bty.css';
import '../../css/s/soci7ctjl.css';
import '../../css/a/a2at6rjqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6j0c_bty"/><circle class="soci7ctjl"/><path class="a2at6rjqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:color-palette-outline" {...props}></Icon>
