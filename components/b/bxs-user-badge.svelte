<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebnfz9bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebnfz9bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-user-badge" {...props}></Icon>
