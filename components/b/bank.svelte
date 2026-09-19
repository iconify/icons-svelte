<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8bbxr3ye.css';
import '../../css/i/i28ld-2jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8bbxr3ye duoicon-secondary-layer"/><path class="duoicon-primary-layer i28ld-2jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:bank" {...props}></Icon>
