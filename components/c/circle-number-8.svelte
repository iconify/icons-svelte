<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnzkjzb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mnzkjzb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-number-8" {...props}></Icon>
