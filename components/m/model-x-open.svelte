<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl9d9xb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl9d9xb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:model-x-open" {...props}></Icon>
