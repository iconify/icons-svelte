<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkid2hbfq.css';
import '../../css/f/fqaz6r90g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkid2hbfq"/><path class="fqaz6r90g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:copy-alt-fill" {...props}></Icon>
