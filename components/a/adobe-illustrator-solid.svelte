<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imiobx9sm.css';
import '../../css/k/k4-_ilboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imiobx9sm"/><path clip-rule="evenodd" class="k4-_ilboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-illustrator-solid" {...props}></Icon>
