<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxq2l9bzi.css';
import '../../css/w/w_jw7cb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxq2l9bzi"/><path clip-rule="evenodd" class="w_jw7cb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:box-open-fill-duotone" {...props}></Icon>
