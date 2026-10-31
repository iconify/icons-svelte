<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z726f_ufb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z726f_ufb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:infinity-20-solid" {...props}></Icon>
