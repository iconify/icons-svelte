<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwgfh2bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwgfh2bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-up-right-from-square" {...props}></Icon>
