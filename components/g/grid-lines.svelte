<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emb9gnbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emb9gnbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-lines" {...props}></Icon>
