<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szr8xwb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="szr8xwb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lottery" {...props}></Icon>
