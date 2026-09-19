<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acv3zackm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="acv3zackm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gift-fill" {...props}></Icon>
