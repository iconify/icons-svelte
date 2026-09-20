<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7azwk40j.css';
import '../../css/z/zx-jj4ivt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7azwk40j"/><path class="zx-jj4ivt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:conv" {...props}></Icon>
