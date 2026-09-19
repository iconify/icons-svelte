<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-h1lxbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v-h1lxbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-pak-manta-automated-data-lineage" {...props}></Icon>
