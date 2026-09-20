<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go-kqbbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="go-kqbbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-check2" {...props}></Icon>
