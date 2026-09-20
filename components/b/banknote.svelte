<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjrtdbcmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xjrtdbcmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:banknote" {...props}></Icon>
