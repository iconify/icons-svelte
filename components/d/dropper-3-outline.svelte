<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er09-obpj.css';
import '../../css/w/w_8qokj7u.css';
import '../../css/k/ku79fqbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er09-obpj"/><path class="w_8qokj7u"/><path clip-rule="evenodd" class="ku79fqbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dropper-3-outline" {...props}></Icon>
