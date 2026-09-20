<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-_crhveu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="v-_crhveu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:notification" {...props}></Icon>
