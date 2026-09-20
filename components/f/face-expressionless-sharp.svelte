<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa7v1s--s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa7v1s--s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-expressionless-sharp" {...props}></Icon>
