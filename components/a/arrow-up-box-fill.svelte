<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3jf67bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3jf67bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-box-fill" {...props}></Icon>
