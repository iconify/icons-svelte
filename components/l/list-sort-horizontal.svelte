<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au88ctbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au88ctbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-sort-horizontal" {...props}></Icon>
