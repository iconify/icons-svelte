<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajkar9b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ajkar9b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-up-left-solid" {...props}></Icon>
