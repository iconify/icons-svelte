<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-dgc_7wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c-dgc_7wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:eyes-look-right" {...props}></Icon>
