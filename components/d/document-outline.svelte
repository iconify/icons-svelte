<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b73k0pm-y.css';
import '../../css/v/v1qktebkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b73k0pm-y"/><path clip-rule="evenodd" class="v1qktebkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:document-outline" {...props}></Icon>
