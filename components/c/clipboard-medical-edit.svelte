<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3rpl4bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3rpl4bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-medical-edit" {...props}></Icon>
