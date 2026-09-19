<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icn-0wbfj.css';
import '../../css/d/dnot0zbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icn-0wbfj"/><path class="dnot0zbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-search-filled" {...props}></Icon>
