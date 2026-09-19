<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-qe7cb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v-qe7cb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-down-on-square" {...props}></Icon>
