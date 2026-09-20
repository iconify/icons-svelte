<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6bqpgb6d.css';
import '../../css/r/rasj23r5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v6bqpgb6d"/><path class="rasj23r5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:flag-checkered" {...props}></Icon>
