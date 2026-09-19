<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq_pgtbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hq_pgtbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-badge-plus" {...props}></Icon>
