<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccyzdizjg.css';
import '../../css/b/bfvy_zbha.css';
import '../../css/q/q1sggqbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccyzdizjg"/><path class="bfvy_zbha"/><path clip-rule="evenodd" class="q1sggqbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:refresh-circle-outline" {...props}></Icon>
