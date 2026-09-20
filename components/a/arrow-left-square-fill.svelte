<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg2ok617q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sg2ok617q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-left-square-fill" {...props}></Icon>
