<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht4j-tbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ht4j-tbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-info-fill" {...props}></Icon>
