<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at3jokbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at3jokbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:download" {...props}></Icon>
