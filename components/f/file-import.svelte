<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu1-mmbtf.css';
import '../../css/n/n3w3yo25d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu1-mmbtf"/><path class="n3w3yo25d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:file-import" {...props}></Icon>
