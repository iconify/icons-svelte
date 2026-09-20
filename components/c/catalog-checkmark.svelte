<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd97r8uzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sd97r8uzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:catalog-checkmark" {...props}></Icon>
