<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk32t904i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yk32t904i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:id-card-sharp-fill" {...props}></Icon>
