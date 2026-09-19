<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzo6b5oqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzo6b5oqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:code-bracket" {...props}></Icon>
