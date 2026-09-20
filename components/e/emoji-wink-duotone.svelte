<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee-ri3mqs.css';
import '../../css/j/jzy1ukxea.css';
import '../../css/a/a7dxfdctp.css';
import '../../css/b/btlc75bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ee-ri3mqs"/><path class="jzy1ukxea"/><path clip-rule="evenodd" class="a7dxfdctp"/><path clip-rule="evenodd" class="btlc75bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:emoji-wink-duotone" {...props}></Icon>
