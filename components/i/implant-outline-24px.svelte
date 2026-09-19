<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inyiadczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inyiadczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:implant-outline-24px" {...props}></Icon>
