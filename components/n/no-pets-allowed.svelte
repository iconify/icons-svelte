<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_cq0-cvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_cq0-cvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-pets-allowed" {...props}></Icon>
