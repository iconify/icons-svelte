<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj8uj2zta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xj8uj2zta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:database-solid" {...props}></Icon>
