<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svd6oabux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svd6oabux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bacon-alt-filled" {...props}></Icon>
