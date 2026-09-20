<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/o6mnyfb7a.css';
import '../../css/a/a1wks9bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="o6mnyfb7a"/><path class="a1wks9bmb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:explicit-content-light" {...props}></Icon>
