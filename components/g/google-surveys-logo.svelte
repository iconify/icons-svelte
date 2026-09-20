<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/r/rsibg6b6a.css';
import '../../css/n/ntre0bcvq.css';
import '../../css/t/tnpfj3tul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="rsibg6b6a"/><path clip-rule="evenodd" class="ntre0bcvq"/><path class="tnpfj3tul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-surveys-logo" {...props}></Icon>
