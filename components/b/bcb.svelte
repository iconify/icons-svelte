<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcxdw0blf.css';
import '../../css/b/bxxmg1bnf.css';
import '../../css/c/cf5h_9dkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcxdw0blf"/><path class="bxxmg1bnf"/><path class="cf5h_9dkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bcb" {...props}></Icon>
