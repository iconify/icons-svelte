<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/truvx-bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="truvx-bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:form-filled" {...props}></Icon>
