<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofy64gejk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ofy64gejk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:atom-editor" {...props}></Icon>
