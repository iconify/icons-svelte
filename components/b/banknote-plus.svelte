<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urbb0o_je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urbb0o_je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-plus" {...props}></Icon>
