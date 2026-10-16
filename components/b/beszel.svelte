<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3u1gj-mw.css';
import '../../css/w/wp3_6pk_p.css';
import '../../css/o/o2a-srg1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":70};
const content = `<defs><linearGradient id="SVGuBr77bNw" x1="0%" x2="100%" y1="20%" y2="120%"><stop offset="0%" class="x3u1gj-mw"/><stop offset="100%" class="wp3_6pk_p"/></linearGradient></defs><path fill="url(#SVGuBr77bNw)" class="o2a-srg1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:beszel" {...props}></Icon>
