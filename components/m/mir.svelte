<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzpv-qb5n.css';
import '../../css/f/fx3jtffrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nzpv-qb5n"/><path class="fx3jtffrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mir" {...props}></Icon>
