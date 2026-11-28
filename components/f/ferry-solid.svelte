<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb45z8maj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb45z8maj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ferry-solid" {...props}></Icon>
