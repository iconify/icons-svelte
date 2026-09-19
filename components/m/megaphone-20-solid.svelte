<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfkqo-b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dfkqo-b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:megaphone-20-solid" {...props}></Icon>
