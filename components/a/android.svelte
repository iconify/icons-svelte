<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8q9e4bsf.css';
import '../../css/m/mgi81ojmu.css';
import '../../css/n/nyrfs3b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8q9e4bsf"/><circle class="mgi81ojmu"/><circle class="nyrfs3b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:android" {...props}></Icon>
