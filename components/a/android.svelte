<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bi49tuoiu.css';
import '../../css/k/kzun96hrq.css';
import '../../css/i/icg4i3brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bi49tuoiu"/><circle class="kzun96hrq"/><circle class="icg4i3brj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:android" {...props}></Icon>
