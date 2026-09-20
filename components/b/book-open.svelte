<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3sus5brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3sus5brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:book-open" {...props}></Icon>
