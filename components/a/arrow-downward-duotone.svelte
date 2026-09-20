<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwfwcdbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwfwcdbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-downward-duotone" {...props}></Icon>
