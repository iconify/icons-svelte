<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baavd1mxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baavd1mxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mails-fill" {...props}></Icon>
