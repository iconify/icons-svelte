<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az85j8l9o.css';
import '../../css/c/cnhx37y6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="az85j8l9o"/><path class="cnhx37y6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magic-stick-outline" {...props}></Icon>
