<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4uf1qb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4uf1qb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:alert-fill" {...props}></Icon>
