<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9slh7bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9slh7bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:paper-bag" {...props}></Icon>
