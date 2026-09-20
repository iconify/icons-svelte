<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciut39q6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ciut39q6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-one" {...props}></Icon>
