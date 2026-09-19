<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-qzc0b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v-qzc0b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file" {...props}></Icon>
