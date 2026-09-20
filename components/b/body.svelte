<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyqqgj92a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tyqqgj92a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:body" {...props}></Icon>
