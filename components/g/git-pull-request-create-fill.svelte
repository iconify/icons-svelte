<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acrf5cy9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acrf5cy9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-create-fill" {...props}></Icon>
