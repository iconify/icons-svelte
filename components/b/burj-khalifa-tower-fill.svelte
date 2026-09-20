<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcysl7box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hcysl7box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:burj-khalifa-tower-fill" {...props}></Icon>
