<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddaedubdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddaedubdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:edit-alt" {...props}></Icon>
