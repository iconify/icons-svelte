<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9af1acuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9af1acuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:layout-kanban" {...props}></Icon>
