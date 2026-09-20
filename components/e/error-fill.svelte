<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt2f7cbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gt2f7cbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:error-fill" {...props}></Icon>
