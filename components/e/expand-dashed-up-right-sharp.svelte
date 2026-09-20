<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_toq0bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_toq0bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-up-right-sharp" {...props}></Icon>
