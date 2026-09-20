<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c54sfd9tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c54sfd9tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chess-rook" {...props}></Icon>
