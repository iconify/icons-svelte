<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcadem75o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcadem75o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:no-entry" {...props}></Icon>
