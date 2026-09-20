<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie4nicb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ie4nicb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earbuds-charge" {...props}></Icon>
