<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9t6xzb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9t6xzb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pull-request-check" {...props}></Icon>
