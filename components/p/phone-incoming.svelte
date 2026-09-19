<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1madqn3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1madqn3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:phone-incoming" {...props}></Icon>
