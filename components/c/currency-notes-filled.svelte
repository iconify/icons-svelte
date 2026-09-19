<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rojie2byc.css';
import '../../css/z/zooty4bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rojie2byc"/><path class="zooty4bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:currency-notes-filled" {...props}></Icon>
