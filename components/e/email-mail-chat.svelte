<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acmwlabsp.css';
import '../../css/h/hzlua-bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="acmwlabsp"/><path class="hzlua-bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:email-mail-chat" {...props}></Icon>
