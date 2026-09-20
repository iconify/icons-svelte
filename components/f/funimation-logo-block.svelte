<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b03i_1hqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b03i_1hqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:funimation-logo-block" {...props}></Icon>
