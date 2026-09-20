<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/e/eup04y.css';
import '../../css/g/g2ouze.css';
import '../../css/p/pl-mjc.css';
import '../../css/x/xxwxit.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c eup04y"/><path class="a0m25c g2ouze"/><path class="a0m25c pl-mjc"/><path class="a0m25c xxwxit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:email-alert" {...props}></Icon>
