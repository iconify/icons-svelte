<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi3jvebpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qi3jvebpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-x" {...props}></Icon>
