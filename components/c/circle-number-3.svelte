<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv9qadb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qv9qadb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-number-3" {...props}></Icon>
