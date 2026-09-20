<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aheklhggy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aheklhggy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chair" {...props}></Icon>
