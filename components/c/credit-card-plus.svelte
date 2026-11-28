<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajgk8lboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajgk8lboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:credit-card-plus" {...props}></Icon>
