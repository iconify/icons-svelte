<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngqnlhnvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ngqnlhnvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-5-fill" {...props}></Icon>
