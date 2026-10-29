<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5zdp7brd.css';
import '../../css/q/q1fnmujdu.css';
import '../../css/b/bjuc6lcvi.css';
import '../../css/j/jmj296b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5zdp7brd wm-k"/><path class="q1fnmujdu wm-k"/><path class="bjuc6lcvi wm-a"/><path class="jmj296b2v wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:layout-list" {...props}></Icon>
