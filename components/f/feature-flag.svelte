<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_o-v-b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x_o-v-b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:feature-flag" {...props}></Icon>
