<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmu6wq9zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmu6wq9zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clipboard-list" {...props}></Icon>
