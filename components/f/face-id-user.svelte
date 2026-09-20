<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvt9swbvw.css';
import '../../css/z/zzlsuxo-a.css';
import '../../css/f/fd5mkxbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fvt9swbvw"/><path class="zzlsuxo-a"/><path class="fd5mkxbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:face-id-user" {...props}></Icon>
