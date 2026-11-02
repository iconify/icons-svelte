<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz18w6tjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz18w6tjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:burj-al-arab-line" {...props}></Icon>
