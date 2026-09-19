<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh_w3wmue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gh_w3wmue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:malnutrition" {...props}></Icon>
