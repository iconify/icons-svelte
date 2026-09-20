<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln_2etbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln_2etbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:airpods-open-fill" {...props}></Icon>
