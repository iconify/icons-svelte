<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guq9ui5hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":832,"height":1024};
const content = `<path class="guq9ui5hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:coffeecupalt" {...props}></Icon>
