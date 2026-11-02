<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmv069b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmv069b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-shekel-2-fill" {...props}></Icon>
