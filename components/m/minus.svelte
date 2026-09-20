<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keum6jv7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="keum6jv7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:minus" {...props}></Icon>
