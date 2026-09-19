<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrij0bbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nrij0bbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:plus" {...props}></Icon>
