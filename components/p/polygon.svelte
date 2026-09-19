<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul4cwdbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ul4cwdbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:polygon" {...props}></Icon>
