<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6ffl6b-d.css';
import '../../css/c/czuc2kb0l.css';
import '../../css/b/bphnj6bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6ffl6b-d"/><path clip-rule="evenodd" class="czuc2kb0l"/><path clip-rule="evenodd" class="bphnj6bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:dropbox" {...props}></Icon>
