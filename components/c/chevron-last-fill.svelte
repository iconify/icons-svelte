<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odlg4gbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odlg4gbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chevron-last-fill" {...props}></Icon>
